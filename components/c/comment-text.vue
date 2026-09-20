<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x93_19b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x93_19b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:comment-text" /></template>
