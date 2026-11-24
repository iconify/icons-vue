<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5q_y96bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5q_y96bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:boxes-linked-filled" /></template>
