<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4eqr1bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4eqr1bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:heart-full-outline" /></template>
