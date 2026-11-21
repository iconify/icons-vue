<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkqd60bly.css';
import '../../css/y/y_icihb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xkqd60bly"/><path class="y_icihb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-cog-filled" /></template>
