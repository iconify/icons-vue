<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnzyukykk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnzyukykk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-up-to-line-fill-round" /></template>
