<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvtud_y2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvtud_y2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:decentraland" /></template>
