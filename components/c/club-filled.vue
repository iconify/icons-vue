<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygh1u7suj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygh1u7suj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:club-filled" /></template>
