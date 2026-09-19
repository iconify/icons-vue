<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq6sr08fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq6sr08fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dartboard" /></template>
