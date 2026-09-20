<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmc00ibtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmc00ibtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:cart-arrow-down" /></template>
