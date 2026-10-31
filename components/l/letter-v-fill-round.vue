<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1rvn5bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1rvn5bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-v-fill-round" /></template>
