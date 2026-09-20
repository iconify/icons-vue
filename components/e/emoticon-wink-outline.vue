<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2jba5bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2jba5bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-wink-outline" /></template>
