<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no2d46b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="no2d46b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-pause-filled" /></template>
