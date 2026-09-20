<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpdtolbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpdtolbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:document-like-filled" /></template>
