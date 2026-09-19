<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efz1s0b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efz1s0b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-baguette" /></template>
