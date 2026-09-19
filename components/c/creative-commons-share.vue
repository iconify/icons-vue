<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj_6xpl-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xj_6xpl-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:creative-commons-share" /></template>
