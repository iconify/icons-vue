<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_xf5hb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="y_xf5hb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:handtwofingers" /></template>
