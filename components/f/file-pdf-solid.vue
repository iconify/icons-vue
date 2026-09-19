<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc8ekq55e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xc8ekq55e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-pdf-solid" /></template>
