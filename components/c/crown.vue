<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sguv65_5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sguv65_5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:crown" /></template>
