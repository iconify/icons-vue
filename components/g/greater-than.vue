<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il392qm0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="il392qm0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:greater-than" /></template>
