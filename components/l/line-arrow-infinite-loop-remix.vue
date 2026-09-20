<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc5f9ceih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vc5f9ceih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-infinite-loop-remix" /></template>
