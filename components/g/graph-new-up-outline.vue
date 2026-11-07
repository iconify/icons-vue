<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj6z6-b0q.css';
import '../../css/p/p9-c1gbhj.css';
import '../../css/e/eo7u7db2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj6z6-b0q"/><path clip-rule="evenodd" class="p9-c1gbhj"/><path class="eo7u7db2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-new-up-outline" /></template>
