<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw0w95kpx.css';
import '../../css/b/b1gwc0q-o.css';
import '../../css/y/ymyomxbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="rw0w95kpx"/><path class="b1gwc0q-o"/><path class="ymyomxbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:chart" /></template>
