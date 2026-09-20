<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q79-pfb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q79-pfb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-plus" /></template>
