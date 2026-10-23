<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldaauxbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldaauxbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:graph-hub-filled" /></template>
