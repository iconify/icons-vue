<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gln2ec9ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gln2ec9ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cube-solid" /></template>
