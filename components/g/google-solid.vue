<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs-bohb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vs-bohb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:google-solid" /></template>
