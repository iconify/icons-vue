<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t01qetbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t01qetbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bow-tie-solid" /></template>
