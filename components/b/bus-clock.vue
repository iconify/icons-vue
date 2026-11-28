<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufw7ugvlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufw7ugvlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bus-clock" /></template>
