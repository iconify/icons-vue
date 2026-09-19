<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzt8y6o5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzt8y6o5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:garlands" /></template>
