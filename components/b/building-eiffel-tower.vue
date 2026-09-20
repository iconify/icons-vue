<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flrsyhxrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flrsyhxrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-eiffel-tower" /></template>
