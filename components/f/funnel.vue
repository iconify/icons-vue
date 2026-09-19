<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4jpy0b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d4jpy0b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:funnel" /></template>
