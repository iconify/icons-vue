<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho0wmrbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho0wmrbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:day-sunny" /></template>
