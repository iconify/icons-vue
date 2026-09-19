<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibg-916rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibg-916rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-left-01" /></template>
