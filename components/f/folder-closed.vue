<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw8-seayw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="uw8-seayw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:folder-closed" /></template>
