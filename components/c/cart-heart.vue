<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q339sd64c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q339sd64c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cart-heart" /></template>
