<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpwwhp63x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpwwhp63x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chevron-right-solid" /></template>
