<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx751ebbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bx751ebbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleforwardempty" /></template>
