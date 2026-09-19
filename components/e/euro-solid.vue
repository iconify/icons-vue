<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk-z4kbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wk-z4kbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:euro-solid" /></template>
