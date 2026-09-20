<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx699ab2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx699ab2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-left-thin-circle-outline" /></template>
