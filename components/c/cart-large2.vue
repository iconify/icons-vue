<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0odoebnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0odoebnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-large2" /></template>
