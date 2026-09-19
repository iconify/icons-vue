<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab51tkfnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":384};
const content = `<path class="ab51tkfnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-line-spacing" /></template>
