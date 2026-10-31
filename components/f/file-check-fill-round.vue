<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvm_ht4ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvm_ht4ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-check-fill-round" /></template>
