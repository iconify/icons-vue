<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg7-5s82w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg7-5s82w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:document-add" /></template>
