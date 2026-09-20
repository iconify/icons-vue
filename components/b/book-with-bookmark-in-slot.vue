<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lih5fib8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lih5fib8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-bookmark-in-slot" /></template>
