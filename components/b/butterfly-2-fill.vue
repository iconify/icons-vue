<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj3-3yb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tj3-3yb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:butterfly-2-fill" /></template>
