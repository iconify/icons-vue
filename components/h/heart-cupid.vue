<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp_nt6zvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp_nt6zvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:heart-cupid" /></template>
