<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7k_0nbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7k_0nbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-office" /></template>
