<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv0a2vbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv0a2vbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-left-square-solid" /></template>
