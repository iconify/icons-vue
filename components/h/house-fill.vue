<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m84svr34v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m84svr34v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:house-fill" /></template>
