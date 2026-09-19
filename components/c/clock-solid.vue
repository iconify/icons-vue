<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hch5jjbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hch5jjbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clock-solid" /></template>
