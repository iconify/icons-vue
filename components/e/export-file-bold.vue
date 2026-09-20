<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2j4griqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2j4griqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:export-file-bold" /></template>
