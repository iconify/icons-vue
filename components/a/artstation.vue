<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqkq0jbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lqkq0jbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:artstation" /></template>
