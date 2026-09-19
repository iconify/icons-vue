<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0kol9bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l0kol9bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:arrow-up-left" /></template>
