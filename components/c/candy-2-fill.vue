<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adkeezbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adkeezbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candy-2-fill" /></template>
