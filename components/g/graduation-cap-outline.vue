<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oobgrbcdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oobgrbcdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:graduation-cap-outline" /></template>
