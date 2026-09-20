<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0g2z9f8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0g2z9f8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bracket-curly-solid" /></template>
