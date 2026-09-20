<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-jo04stb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v-jo04stb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:json-document-filled" /></template>
