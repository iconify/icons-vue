<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpe9po6ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpe9po6ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:clipboard-document-list" /></template>
