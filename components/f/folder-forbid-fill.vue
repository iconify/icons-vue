<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4vb5lb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4vb5lb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-forbid-fill" /></template>
