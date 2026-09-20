<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qane7acao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qane7acao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dropbox" /></template>
