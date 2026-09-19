<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcfxrkbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcfxrkbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:glass-water-outline" /></template>
