<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlk993f9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlk993f9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-paanga" /></template>
