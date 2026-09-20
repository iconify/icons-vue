<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai5h96bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai5h96bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arow-to-right-fill" /></template>
