<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utak5gbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utak5gbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:direction" /></template>
