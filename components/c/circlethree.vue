<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvv9p2b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mvv9p2b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlethree" /></template>
