<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt5iptwmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mt5iptwmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:crown" /></template>
