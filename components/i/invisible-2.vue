<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5u7_dbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n5u7_dbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:invisible-2" /></template>
