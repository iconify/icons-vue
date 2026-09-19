<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emb9gnbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emb9gnbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-lines-filled" /></template>
