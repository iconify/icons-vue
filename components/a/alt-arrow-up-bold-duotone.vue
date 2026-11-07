<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anlkm7xov.css';
import '../../css/f/fbtcj0tzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anlkm7xov"/><path class="fbtcj0tzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-up-bold-duotone" /></template>
