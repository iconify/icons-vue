<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nahucow6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nahucow6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:grooveshark-logo-block" /></template>
