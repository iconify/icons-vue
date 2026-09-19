<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu7nefmvr.css';
import '../../css/e/ea0a-8box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":12};
const content = `<path class="tu7nefmvr"/><path class="ea0a-8box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:link" /></template>
