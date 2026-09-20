<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo_m2acat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo_m2acat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-cog" /></template>
