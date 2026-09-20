<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdl-6zbdg.css';
import '../../css/w/w6se-gehu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vdl-6zbdg"/><path class="w6se-gehu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-radiology" /></template>
