<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw766jryt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw766jryt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bread-01" /></template>
