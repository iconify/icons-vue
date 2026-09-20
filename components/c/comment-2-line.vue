<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndlm_riwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndlm_riwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:comment-2-line" /></template>
