<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6txmrbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6txmrbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:editorconfig" /></template>
