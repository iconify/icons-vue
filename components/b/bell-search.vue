<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9odol0ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9odol0ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-search" /></template>
