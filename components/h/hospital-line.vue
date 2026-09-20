<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frpheabca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frpheabca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hospital-line" /></template>
