<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3kj9tbpq.css';
import '../../css/c/cat22_54h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a3kj9tbpq"/><path class="cat22_54h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drop-photo" /></template>
