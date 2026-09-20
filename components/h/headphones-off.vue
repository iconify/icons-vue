<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n235_xbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n235_xbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-off" /></template>
