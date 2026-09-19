<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9mby9bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e9mby9bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:face-angry" /></template>
