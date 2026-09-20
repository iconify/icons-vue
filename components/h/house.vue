<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h61fxzbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h61fxzbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:house" /></template>
