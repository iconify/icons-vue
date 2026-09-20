<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iolxe8bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iolxe8bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:justice-hammer" /></template>
