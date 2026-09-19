<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pad-kj4bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="pad-kj4bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:gg-circle" /></template>
