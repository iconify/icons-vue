<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b85xdcc4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b85xdcc4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:instagram" /></template>
