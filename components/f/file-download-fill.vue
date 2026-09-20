<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-1bwbbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-1bwbbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-download-fill" /></template>
