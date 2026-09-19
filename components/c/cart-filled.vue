<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whjp1dbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whjp1dbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart-filled" /></template>
