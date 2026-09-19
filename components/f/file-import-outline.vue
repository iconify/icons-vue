<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxzwk76vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxzwk76vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-import-outline" /></template>
