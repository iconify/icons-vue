<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp2s87g9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp2s87g9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-nuxt" /></template>
