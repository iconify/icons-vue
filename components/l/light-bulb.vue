<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz_gw_b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz_gw_b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:light-bulb" /></template>
