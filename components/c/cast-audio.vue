<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh86xtb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh86xtb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cast-audio" /></template>
