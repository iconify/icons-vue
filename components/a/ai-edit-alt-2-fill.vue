<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7gugk-gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7gugk-gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-edit-alt-2-fill" /></template>
