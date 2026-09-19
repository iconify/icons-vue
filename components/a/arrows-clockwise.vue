<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsogbbvlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qsogbbvlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrows-clockwise" /></template>
