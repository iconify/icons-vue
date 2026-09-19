<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxj_t4hmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nxj_t4hmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:haze-night-filled" /></template>
