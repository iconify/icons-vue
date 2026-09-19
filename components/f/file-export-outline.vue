<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es8hrw68o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es8hrw68o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-export-outline" /></template>
