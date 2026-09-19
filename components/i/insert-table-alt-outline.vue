<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y96k3lb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y96k3lb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:insert-table-alt-outline" /></template>
