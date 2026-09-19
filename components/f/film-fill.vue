<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9w-19l9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9w-19l9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:film-fill" /></template>
