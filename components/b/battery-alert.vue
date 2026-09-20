<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq5bn3vbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq5bn3vbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-alert" /></template>
