<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlvtd0bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dlvtd0bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-import-solid" /></template>
