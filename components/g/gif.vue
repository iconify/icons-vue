<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i58x1vbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i58x1vbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:gif" /></template>
