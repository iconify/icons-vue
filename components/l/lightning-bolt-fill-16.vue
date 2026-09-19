<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_5w63pry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b_5w63pry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lightning-bolt-fill-16" /></template>
