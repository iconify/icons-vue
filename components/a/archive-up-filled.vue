<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e71r7tbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e71r7tbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:archive-up-filled" /></template>
