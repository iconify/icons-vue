<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7bbfvb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y7bbfvb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-application-screen" /></template>
