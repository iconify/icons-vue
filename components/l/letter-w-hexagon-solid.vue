<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgvx7jbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgvx7jbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-w-hexagon-solid" /></template>
