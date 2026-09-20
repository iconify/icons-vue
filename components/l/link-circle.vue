<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh167rb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oh167rb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:link-circle" /></template>
