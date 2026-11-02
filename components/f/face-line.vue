<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/behhjsymg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="behhjsymg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:face-line" /></template>
