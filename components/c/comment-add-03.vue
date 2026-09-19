<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-dw5ob4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-dw5ob4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:comment-add-03" /></template>
