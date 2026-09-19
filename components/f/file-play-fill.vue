<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prwyleb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="prwyleb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-play-fill" /></template>
