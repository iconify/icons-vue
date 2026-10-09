<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agva6viha.css';
import '../../css/m/mb4eqwb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="agva6viha"/><path class="mb4eqwb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chef-knife-20-bold" /></template>
