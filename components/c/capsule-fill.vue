<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3j60pb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3j60pb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:capsule-fill" /></template>
