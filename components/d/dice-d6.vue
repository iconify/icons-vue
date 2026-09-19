<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg9evwbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sg9evwbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dice-d6" /></template>
