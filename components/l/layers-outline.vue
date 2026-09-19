<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m53y9kbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m53y9kbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:layers-outline" /></template>
