<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d80qkebvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d80qkebvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-deploy-filled" /></template>
