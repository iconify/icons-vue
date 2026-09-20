<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuosp9q_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuosp9q_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apache-lucene" /></template>
