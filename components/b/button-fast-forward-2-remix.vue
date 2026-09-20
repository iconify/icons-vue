<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg1la2bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qg1la2bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-fast-forward-2-remix" /></template>
