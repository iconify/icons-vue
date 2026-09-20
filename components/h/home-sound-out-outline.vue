<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0cqydxux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0cqydxux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-sound-out-outline" /></template>
