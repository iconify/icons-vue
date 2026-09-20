<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ony6rypgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ony6rypgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:credit-card-4-remix" /></template>
