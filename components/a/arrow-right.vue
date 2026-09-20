<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1e1eib7x.css';
import '../../css/f/f1pn7ybqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="o1e1eib7x"/><path class="f1pn7ybqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:arrow-right" /></template>
