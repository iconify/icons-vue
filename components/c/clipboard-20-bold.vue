<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0rmdbc9t.css';
import '../../css/c/cdt91-3up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x0rmdbc9t"/><path class="cdt91-3up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-20-bold" /></template>
