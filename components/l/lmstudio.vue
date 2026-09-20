<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg-d_6rce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg-d_6rce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lmstudio" /></template>
