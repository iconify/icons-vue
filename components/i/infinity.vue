<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf_c2vbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf_c2vbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:infinity" /></template>
