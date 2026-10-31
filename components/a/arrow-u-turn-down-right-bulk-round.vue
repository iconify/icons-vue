<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntejkxhrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntejkxhrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-down-right-bulk-round" /></template>
