<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x07oq7k1t.css';
import '../../css/b/b53sk69qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x07oq7k1t"/><path class="b53sk69qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bookmark-check-20-bold" /></template>
