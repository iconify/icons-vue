<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b918qp0xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b918qp0xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-5-bold" /></template>
