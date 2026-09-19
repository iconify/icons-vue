<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-deq81w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v7-deq81w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-down-doc-fill" /></template>
