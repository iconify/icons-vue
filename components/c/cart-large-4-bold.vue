<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezvnicbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezvnicbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-large-4-bold" /></template>
