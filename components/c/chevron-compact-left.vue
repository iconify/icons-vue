<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe0v8glqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fe0v8glqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-compact-left" /></template>
