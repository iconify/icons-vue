<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eof5pzb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="eof5pzb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left-circle-fill" /></template>
