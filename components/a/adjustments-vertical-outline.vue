<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngw-7mbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngw-7mbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:adjustments-vertical-outline" /></template>
