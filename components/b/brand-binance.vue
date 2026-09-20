<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4x099b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4x099b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-binance" /></template>
