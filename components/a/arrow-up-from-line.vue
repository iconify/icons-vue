<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn6l8cb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn6l8cb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-from-line" /></template>
