<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7tq-ebjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7tq-ebjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-up" /></template>
