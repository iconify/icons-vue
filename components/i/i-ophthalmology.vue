<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohgar4mkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ohgar4mkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-ophthalmology" /></template>
