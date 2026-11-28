<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qojzlrxcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qojzlrxcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-text-solid" /></template>
