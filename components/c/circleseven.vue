<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oil8jkbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oil8jkbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleseven" /></template>
