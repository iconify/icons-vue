<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck017qboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck017qboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:arrow-right" /></template>
