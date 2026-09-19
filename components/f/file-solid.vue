<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5wh2ubgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5wh2ubgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-solid" /></template>
