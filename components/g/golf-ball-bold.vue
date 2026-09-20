<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ja66rng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_ja66rng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:golf-ball-bold" /></template>
