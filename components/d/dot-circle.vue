<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7fwh78cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z7fwh78cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:dot-circle" /></template>
