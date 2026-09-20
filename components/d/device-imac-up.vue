<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqjz04cwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqjz04cwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-up" /></template>
