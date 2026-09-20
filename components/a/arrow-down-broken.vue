<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjbuujh0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjbuujh0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-down-broken" /></template>
