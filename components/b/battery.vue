<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnux_zuii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jnux_zuii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:battery" /></template>
