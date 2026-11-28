<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgvtg0iqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgvtg0iqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-down-solid" /></template>
