<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2_rusbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2_rusbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image-filled" /></template>
