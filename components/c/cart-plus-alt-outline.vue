<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvdz23vge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvdz23vge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cart-plus-alt-outline" /></template>
