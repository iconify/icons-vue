<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po4ezxent.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po4ezxent"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-info-alt" /></template>
