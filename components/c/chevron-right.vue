<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh28zeddw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh28zeddw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:chevron-right" /></template>
