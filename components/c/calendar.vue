<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5vp10bfi.css';
import '../../css/k/k1vbm5bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer v5vp10bfi"/><path class="duoicon-primary-layer k1vbm5bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:calendar" /></template>
