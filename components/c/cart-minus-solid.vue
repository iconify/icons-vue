<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0-s0sb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0-s0sb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cart-minus-solid" /></template>
