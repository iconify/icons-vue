<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvfcz2blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvfcz2blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-trending-down" /></template>
