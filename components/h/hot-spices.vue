<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcbv1h3kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcbv1h3kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hot-spices" /></template>
