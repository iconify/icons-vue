<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj126jb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj126jb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-tether" /></template>
