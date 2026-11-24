<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2gpqkf8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2gpqkf8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:guitar-electric-filled" /></template>
