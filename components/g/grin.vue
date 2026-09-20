<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4e20ho8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4e20ho8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:grin" /></template>
