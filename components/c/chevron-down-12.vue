<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxuitzbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="vxuitzbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-down-12" /></template>
