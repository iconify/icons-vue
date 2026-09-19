<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr4hulbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr4hulbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-sound" /></template>
