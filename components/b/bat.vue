<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqu-4rbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqu-4rbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bat" /></template>
