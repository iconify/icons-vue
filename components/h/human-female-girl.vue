<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvt3r3ygm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvt3r3ygm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-female-girl" /></template>
