<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixfou5b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixfou5b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:animal-products-egg-bold" /></template>
