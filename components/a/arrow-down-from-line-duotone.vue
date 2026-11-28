<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klt794f4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klt794f4c primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-from-line-duotone" /></template>
