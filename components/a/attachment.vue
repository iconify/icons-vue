<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lehfdhbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":470,"height":850};
const content = `<path class="lehfdhbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:attachment" /></template>
