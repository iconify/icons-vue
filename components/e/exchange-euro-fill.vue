<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywe0yq7db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywe0yq7db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-euro-fill" /></template>
