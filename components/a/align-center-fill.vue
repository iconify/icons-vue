<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf0invbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf0invbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-center-fill" /></template>
