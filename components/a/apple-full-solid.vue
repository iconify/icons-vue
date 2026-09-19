<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u50sa1e_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u50sa1e_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:apple-full-solid" /></template>
