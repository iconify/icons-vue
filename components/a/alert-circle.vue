<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge482kbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge482kbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:alert-circle" /></template>
