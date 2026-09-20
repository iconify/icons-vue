<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvcue3bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvcue3bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-lanscape-slash" /></template>
