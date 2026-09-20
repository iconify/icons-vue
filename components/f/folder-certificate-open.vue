<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsijkbbus.css';
import '../../css/x/xwlvzbvrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hsijkbbus"/><path class="xwlvzbvrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-certificate-open" /></template>
