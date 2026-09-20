<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqr8lfj3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqr8lfj3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-edit" /></template>
