<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip9fitivl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip9fitivl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:file-download-line" /></template>
