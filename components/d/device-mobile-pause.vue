<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssvs6gz7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssvs6gz7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-pause" /></template>
