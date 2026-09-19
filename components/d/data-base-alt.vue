<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5erfebgx.css';
import '../../css/a/alv0vrx0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c5erfebgx"/><path class="alv0vrx0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-base-alt" /></template>
