<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw_m9ijfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":385,"height":512};
const content = `<path class="dw_m9ijfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:behat" /></template>
