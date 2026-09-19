<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb8sl1b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb8sl1b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-lock-open" /></template>
