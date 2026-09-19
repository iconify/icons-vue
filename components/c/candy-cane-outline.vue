<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxz7st9fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxz7st9fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:candy-cane-outline" /></template>
