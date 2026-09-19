<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxji21-fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uxji21-fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:close-circle-solid" /></template>
