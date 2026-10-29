<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baz9wuw8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baz9wuw8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-a" /></template>
