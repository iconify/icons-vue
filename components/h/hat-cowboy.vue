<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1nvt7bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c1nvt7bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hat-cowboy" /></template>
