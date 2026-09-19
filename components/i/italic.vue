<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4yfsnzeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="s4yfsnzeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:italic" /></template>
