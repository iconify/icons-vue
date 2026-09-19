<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj2a8g2fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj2a8g2fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:check-filled" /></template>
