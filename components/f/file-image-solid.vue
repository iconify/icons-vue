<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vevo467ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vevo467ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-image-solid" /></template>
