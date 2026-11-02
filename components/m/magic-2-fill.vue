<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zog-z0bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zog-z0bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-2-fill" /></template>
