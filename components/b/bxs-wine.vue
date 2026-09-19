<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6937tb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6937tb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-wine" /></template>
