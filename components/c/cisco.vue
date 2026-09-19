<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j42itw0el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j42itw0el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cisco" /></template>
