<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuq_gnxqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuq_gnxqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ice-water-bold" /></template>
