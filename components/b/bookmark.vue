<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va-q0lmxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va-q0lmxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark" /></template>
