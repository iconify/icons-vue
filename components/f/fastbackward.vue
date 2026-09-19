<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-i75s6_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k-i75s6_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fastbackward" /></template>
