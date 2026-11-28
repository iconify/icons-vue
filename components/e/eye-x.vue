<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-hg_2b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-hg_2b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:eye-x" /></template>
