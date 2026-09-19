<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgkztrb3w.css';
import '../../css/z/ze7mxibna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgkztrb3w"/><path class="ze7mxibna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-search" /></template>
