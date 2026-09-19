<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r89r5fl9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r89r5fl9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:home-solid" /></template>
