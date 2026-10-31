<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7xtxcb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7xtxcb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-from-line-round" /></template>
