<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlnb7obyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vlnb7obyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:candy-cane" /></template>
