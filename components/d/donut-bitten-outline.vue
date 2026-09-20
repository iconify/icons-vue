<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu2_0m1vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bu2_0m1vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:donut-bitten-outline" /></template>
