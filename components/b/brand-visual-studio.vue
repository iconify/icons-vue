<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suwmr0geo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suwmr0geo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-visual-studio" /></template>
