<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvm4kcb4a.css';
import '../../css/f/fu2jxxb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tvm4kcb4a"/><path class="fu2jxxb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:history" /></template>
