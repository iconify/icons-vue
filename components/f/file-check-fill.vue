<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz67vh9ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz67vh9ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-check-fill" /></template>
