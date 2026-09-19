<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jclt3ehgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jclt3ehgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:filter-dollar-outline" /></template>
