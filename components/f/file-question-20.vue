<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kimfu9q5t.css';
import '../../css/o/ow_xmxbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kimfu9q5t"/><path class="ow_xmxbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-question-20" /></template>
