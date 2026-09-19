<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksnuxy52m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksnuxy52m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bookmark-outline" /></template>
