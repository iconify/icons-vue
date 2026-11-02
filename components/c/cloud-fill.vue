<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unyy2gbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unyy2gbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-fill" /></template>
