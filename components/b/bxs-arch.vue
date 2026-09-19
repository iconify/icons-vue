<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb_fm0b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb_fm0b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-arch" /></template>
