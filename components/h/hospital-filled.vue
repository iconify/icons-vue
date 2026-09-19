<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqmo_eb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqmo_eb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hospital-filled" /></template>
