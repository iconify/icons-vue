<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvk-xsbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vvk-xsbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:dice" /></template>
