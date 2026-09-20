<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kecog9byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kecog9byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:activity" /></template>
