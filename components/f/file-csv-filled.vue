<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow7yhgbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ow7yhgbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-csv-filled" /></template>
