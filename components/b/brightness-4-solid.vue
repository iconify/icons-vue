<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr8pc26yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lr8pc26yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:brightness-4-solid" /></template>
