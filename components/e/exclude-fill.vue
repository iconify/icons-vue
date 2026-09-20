<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndzc9_vnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndzc9_vnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exclude-fill" /></template>
