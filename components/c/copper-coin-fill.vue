<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gozyvab6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gozyvab6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:copper-coin-fill" /></template>
