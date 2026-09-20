<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdxdovb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdxdovb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:google-line" /></template>
