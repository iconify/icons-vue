<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4gq_zbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4gq_zbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bell-active-alt-solid" /></template>
