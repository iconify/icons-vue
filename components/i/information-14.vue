<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhwxi5bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rhwxi5bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:information-14" /></template>
