<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj9ek9a7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uj9ek9a7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-search-solid" /></template>
