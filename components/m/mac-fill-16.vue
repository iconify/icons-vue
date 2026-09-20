<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox7k1oi8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ox7k1oi8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mac-fill-16" /></template>
