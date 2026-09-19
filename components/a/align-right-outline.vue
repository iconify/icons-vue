<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfnjqrb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfnjqrb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:align-right-outline" /></template>
