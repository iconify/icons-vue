<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl0hz87mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl0hz87mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-box-top-left" /></template>
