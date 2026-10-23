<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6-4dugws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6-4dugws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-left" /></template>
