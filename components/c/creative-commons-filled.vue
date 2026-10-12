<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz4a96jsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nz4a96jsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:creative-commons-filled" /></template>
