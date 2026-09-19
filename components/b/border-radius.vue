<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efff6o-je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efff6o-je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:border-radius" /></template>
