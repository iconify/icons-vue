<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gli25bb3i.css';
import '../../css/j/jpkklnhzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gli25bb3i"/><path class="jpkklnhzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cow-20-bold" /></template>
