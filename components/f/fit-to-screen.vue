<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz5xefbiq.css';
import '../../css/a/am0b34b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zz5xefbiq"/><path class="am0b34b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fit-to-screen" /></template>
