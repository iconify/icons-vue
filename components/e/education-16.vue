<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf7r-wbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zf7r-wbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:education-16" /></template>
