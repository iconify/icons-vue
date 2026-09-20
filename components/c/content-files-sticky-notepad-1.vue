<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi01iacmk.css';
import '../../css/r/rghyt8iyb.css';
import '../../css/z/zqb02xggr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bi01iacmk"/><path class="rghyt8iyb"/><path class="zqb02xggr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-sticky-notepad-1" /></template>
