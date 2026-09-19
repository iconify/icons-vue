<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idkx_pblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idkx_pblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-upload" /></template>
