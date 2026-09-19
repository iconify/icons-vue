<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7jyp1b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7jyp1b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:document-arrow-down" /></template>
