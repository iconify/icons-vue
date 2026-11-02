<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu2ac0b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu2ac0b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-up-from-dot-line" /></template>
