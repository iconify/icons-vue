<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts7g1fbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ts7g1fbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:croissant-filled" /></template>
