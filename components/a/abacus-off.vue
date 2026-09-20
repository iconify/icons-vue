<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya3dkm1ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya3dkm1ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:abacus-off" /></template>
