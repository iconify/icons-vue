<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-zpdzu1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-zpdzu1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bell-active-outline" /></template>
