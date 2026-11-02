<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo-0lob9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo-0lob9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-love-line" /></template>
