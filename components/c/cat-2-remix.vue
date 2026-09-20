<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_kk2vjms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a_kk2vjms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cat-2-remix" /></template>
