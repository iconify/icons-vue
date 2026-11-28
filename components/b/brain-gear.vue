<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4pdn--np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4pdn--np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:brain-gear" /></template>
