<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n01ij7bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="n01ij7bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:chevronup" /></template>
