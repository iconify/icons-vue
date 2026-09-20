<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2lh2ub1f.css';
import '../../css/c/c2zv7fbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b2lh2ub1f"/><path class="c2zv7fbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:history" /></template>
