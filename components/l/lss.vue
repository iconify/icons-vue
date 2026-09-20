<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rskug9wwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rskug9wwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lss" /></template>
