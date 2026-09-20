<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk5azdbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk5azdbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:led-strip-variant-off" /></template>
