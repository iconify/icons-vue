<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf6h0-b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf6h0-b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:keyboard-solid" /></template>
