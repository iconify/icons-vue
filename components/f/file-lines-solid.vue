<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga5op1ncr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ga5op1ncr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-lines-solid" /></template>
