<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_i3iqatv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_i3iqatv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:battery-empty" /></template>
