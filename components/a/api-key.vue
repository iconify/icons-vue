<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m223cpbhr.css';
import '../../css/p/pr_1mzb5o.css';
import '../../css/c/cc-gngndl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m223cpbhr"/><circle class="pr_1mzb5o"/><path class="cc-gngndl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:api-key" /></template>
