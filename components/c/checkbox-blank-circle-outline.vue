<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h51m56u_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h51m56u_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbox-blank-circle-outline" /></template>
