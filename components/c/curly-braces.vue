<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acmnv-6wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acmnv-6wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:curly-braces" /></template>
