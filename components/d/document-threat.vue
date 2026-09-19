<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se8-wzb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se8-wzb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-threat" /></template>
