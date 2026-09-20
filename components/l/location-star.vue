<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceqlhwbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceqlhwbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-star" /></template>
