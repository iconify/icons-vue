<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_mh1h_-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_mh1h_-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cloudy-2-fill" /></template>
