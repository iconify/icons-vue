<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgl32slbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jgl32slbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:circle" /></template>
