<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw3rfebax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw3rfebax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:cross-small" /></template>
