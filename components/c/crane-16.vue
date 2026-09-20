<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy6bdibix.css';
import '../../css/g/gvxfo6vqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hy6bdibix"/><path clip-rule="evenodd" class="gvxfo6vqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:crane-16" /></template>
