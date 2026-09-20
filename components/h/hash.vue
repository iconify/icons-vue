<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysw8-qyyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ysw8-qyyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:hash" /></template>
