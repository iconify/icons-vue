<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwtv-rx-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwtv-rx-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bell-ring" /></template>
