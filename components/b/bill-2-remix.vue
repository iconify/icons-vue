<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0hu3wbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s0hu3wbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bill-2-remix" /></template>
