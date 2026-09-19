<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1a24nbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1a24nbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:badge-exclamation-filled" /></template>
