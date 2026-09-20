<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o26r6hdrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o26r6hdrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-lock-outline" /></template>
