<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcp8k2ckv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vcp8k2ckv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clipboard-type-filled" /></template>
