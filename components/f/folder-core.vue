<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch5-wbctd.css';
import '../../css/j/ja8mq8bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ch5-wbctd"/><path class="ja8mq8bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-core" /></template>
