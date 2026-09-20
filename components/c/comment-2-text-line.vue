<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlx5a_q8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlx5a_q8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:comment-2-text-line" /></template>
