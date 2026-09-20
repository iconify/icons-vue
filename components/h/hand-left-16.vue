<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wse6bfb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wse6bfb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hand-left-16" /></template>
