<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djseinb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djseinb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-audio-solid" /></template>
