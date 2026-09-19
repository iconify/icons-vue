<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxi3aebem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxi3aebem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:curvy-left-right-direction" /></template>
