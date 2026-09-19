<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0_cad3dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p0_cad3dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:caret-right-solid" /></template>
