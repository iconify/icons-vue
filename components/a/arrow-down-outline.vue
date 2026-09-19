<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o88emhyfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o88emhyfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-down-outline" /></template>
