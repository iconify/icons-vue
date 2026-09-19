<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9kx0un3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9kx0un3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:license-no" /></template>
