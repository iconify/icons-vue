<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_75qsb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_75qsb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-text-filled" /></template>
