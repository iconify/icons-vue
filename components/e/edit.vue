<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1r28zbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1r28zbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:edit" /></template>
