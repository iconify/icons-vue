<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmviaubyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xmviaubyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:c-plus-plus-language" /></template>
