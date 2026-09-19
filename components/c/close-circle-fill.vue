<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhh-_dwpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhh-_dwpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:close-circle-fill" /></template>
