<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze7hdcc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze7hdcc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-documents-solid" /></template>
