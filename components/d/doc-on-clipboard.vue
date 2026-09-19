<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5m9fgbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d5m9fgbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-on-clipboard" /></template>
