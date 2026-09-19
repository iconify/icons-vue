<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqf92tbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqf92tbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:link-solid" /></template>
