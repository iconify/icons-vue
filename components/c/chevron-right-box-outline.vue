<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr5k80rzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr5k80rzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-right-box-outline" /></template>
