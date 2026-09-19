<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkdrclbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkdrclbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:distribute-horizontal-left" /></template>
