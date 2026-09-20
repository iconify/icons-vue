<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7-hzvbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7-hzvbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-fill" /></template>
