<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adkf8dbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adkf8dbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-volume" /></template>
