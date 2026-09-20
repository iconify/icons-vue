<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hea445i6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hea445i6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:door-sliding-lock" /></template>
