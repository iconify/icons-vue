<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_2-9c3fr.css';
import '../../css/z/zq-0s9biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s_2-9c3fr"/><path class="zq-0s9biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:label" /></template>
