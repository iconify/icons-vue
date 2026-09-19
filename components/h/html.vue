<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgg4lhbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wgg4lhbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:html" /></template>
