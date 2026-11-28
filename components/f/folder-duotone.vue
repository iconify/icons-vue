<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1iyjg9mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1iyjg9mm primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-duotone" /></template>
