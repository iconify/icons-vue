<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czcl3gbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czcl3gbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-large3" /></template>
