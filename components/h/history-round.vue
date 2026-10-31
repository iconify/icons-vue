<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk78tqloq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk78tqloq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:history-round" /></template>
