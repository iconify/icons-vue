<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ndr7b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ndr7b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-upload-fill-round" /></template>
