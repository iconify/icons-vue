<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuwmmiujp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuwmmiujp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart-check-filled" /></template>
