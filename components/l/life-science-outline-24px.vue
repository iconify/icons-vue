<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1m8crbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u1m8crbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:life-science-outline-24px" /></template>
