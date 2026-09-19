<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l15u55g8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="l15u55g8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:discover" /></template>
