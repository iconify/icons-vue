<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci8hcacek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci8hcacek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chart-outline" /></template>
