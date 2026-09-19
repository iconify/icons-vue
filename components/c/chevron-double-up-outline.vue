<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn24i51gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn24i51gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chevron-double-up-outline" /></template>
