<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4fn36r9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4fn36r9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:concave-double-16" /></template>
