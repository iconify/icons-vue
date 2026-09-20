<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipg4k0btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipg4k0btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-counterclockwise" /></template>
