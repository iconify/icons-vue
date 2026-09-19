<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op64c1b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="op64c1b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-zip-solid" /></template>
