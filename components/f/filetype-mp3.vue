<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5n9agbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b5n9agbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-mp3" /></template>
