<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_0et5b4i.css';
import '../../css/a/axk9wc20s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q_0et5b4i"/><path class="axk9wc20s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-injection" /></template>
