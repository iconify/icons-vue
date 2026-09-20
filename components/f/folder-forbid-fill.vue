<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcfdrebfg.css';
import '../../css/y/y7tchybym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcfdrebfg"/><path clip-rule="evenodd" class="y7tchybym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-forbid-fill" /></template>
