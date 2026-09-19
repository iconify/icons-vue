<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo646nz8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lo646nz8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hotdog" /></template>
