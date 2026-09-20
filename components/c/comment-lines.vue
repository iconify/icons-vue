<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl45_hbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dl45_hbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:comment-lines" /></template>
