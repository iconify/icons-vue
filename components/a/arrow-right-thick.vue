<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj02-s9_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj02-s9_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-right-thick" /></template>
