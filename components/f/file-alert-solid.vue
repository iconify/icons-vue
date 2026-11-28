<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3z-7f-xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3z-7f-xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-alert-solid" /></template>
