<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw0f72b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw0f72b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-check-circle" /></template>
