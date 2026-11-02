<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsri0ubjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsri0ubjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:key-square-line" /></template>
