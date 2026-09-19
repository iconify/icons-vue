<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z28-l3b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z28-l3b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:candy-cane-solid" /></template>
