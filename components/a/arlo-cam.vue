<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq7lwhbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq7lwhbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:arlo-cam" /></template>
