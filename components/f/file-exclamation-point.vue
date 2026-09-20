<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbi3rb6_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbi3rb6_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-exclamation-point" /></template>
