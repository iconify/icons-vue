<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no1d-ebdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no1d-ebdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:close-sidebar-outline" /></template>
