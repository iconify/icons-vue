<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr_k8vliz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr_k8vliz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-blocked-filled" /></template>
