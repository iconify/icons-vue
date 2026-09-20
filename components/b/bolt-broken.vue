<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rck6_bd7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rck6_bd7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bolt-broken" /></template>
