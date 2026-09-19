<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8z9qwbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8z9qwbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:globe-2-fill" /></template>
