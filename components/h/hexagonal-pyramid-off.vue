<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuj4ifyjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuj4ifyjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagonal-pyramid-off" /></template>
