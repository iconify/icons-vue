<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnjy1bc9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qnjy1bc9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:blockquote-20-solid" /></template>
