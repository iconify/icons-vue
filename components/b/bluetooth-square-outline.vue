<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwsndgc_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zwsndgc_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-square-outline" /></template>
