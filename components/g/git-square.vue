<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoxidbb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="zoxidbb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:git-square" /></template>
