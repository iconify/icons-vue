<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceatd5b9s.css';
import '../../css/w/w6jecwb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceatd5b9s"/><path class="w6jecwb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:done-all-fill" /></template>
