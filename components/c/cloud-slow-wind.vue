<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6j498kyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6j498kyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-slow-wind" /></template>
