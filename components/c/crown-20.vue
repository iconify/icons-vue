<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2zzj1mmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m2zzj1mmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crown-20" /></template>
