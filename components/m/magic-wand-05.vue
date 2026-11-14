<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug70ei58j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug70ei58j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:magic-wand-05" /></template>
