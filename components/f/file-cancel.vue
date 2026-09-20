<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vitt06svn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vitt06svn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-cancel" /></template>
