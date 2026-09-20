<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1cpxe_xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1cpxe_xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-line" /></template>
