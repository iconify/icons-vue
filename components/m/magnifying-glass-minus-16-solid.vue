<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zegr1dffz.css';
import '../../css/j/j7-kr4q1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zegr1dffz"/><path clip-rule="evenodd" class="j7-kr4q1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:magnifying-glass-minus-16-solid" /></template>
