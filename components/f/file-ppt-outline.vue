<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yanlb6ipv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yanlb6ipv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-ppt-outline" /></template>
