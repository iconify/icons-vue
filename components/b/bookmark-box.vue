<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci_vnrbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci_vnrbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-box" /></template>
