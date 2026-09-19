<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylx_4ubcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylx_4ubcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:fish-alt-solid" /></template>
