<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-h7_1-zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b-h7_1-zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:brush" /></template>
