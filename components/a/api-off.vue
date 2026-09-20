<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5mj_ubvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5mj_ubvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:api-off" /></template>
