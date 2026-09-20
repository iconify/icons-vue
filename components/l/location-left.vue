<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-mmq9dtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-mmq9dtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-left" /></template>
