<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm1c3abgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="xm1c3abgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:controlpanelalt" /></template>
