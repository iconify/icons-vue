<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dex2nurdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dex2nurdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-6-filled" /></template>
