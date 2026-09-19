<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxvkwlbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxvkwlbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:file-text-fill" /></template>
