<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab4osybgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab4osybgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bowknot-fill" /></template>
