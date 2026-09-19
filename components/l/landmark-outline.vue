<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c03qgemad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c03qgemad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:landmark-outline" /></template>
