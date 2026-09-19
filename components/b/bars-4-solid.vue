<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds9u897kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ds9u897kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-4-solid" /></template>
