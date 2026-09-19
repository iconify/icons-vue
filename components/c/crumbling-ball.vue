<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozkwrm-qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozkwrm-qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crumbling-ball" /></template>
