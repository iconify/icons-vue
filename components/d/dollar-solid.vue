<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd34weaop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hd34weaop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:dollar-solid" /></template>
