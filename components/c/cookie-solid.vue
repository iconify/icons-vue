<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpmyr_clo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpmyr_clo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cookie-solid" /></template>
