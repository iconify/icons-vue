<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v30e-s2jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v30e-s2jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2-fill" /></template>
