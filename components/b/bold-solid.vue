<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_wb-b4hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_wb-b4hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bold-solid" /></template>
