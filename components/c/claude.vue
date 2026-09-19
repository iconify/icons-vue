<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_44m9bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="w_44m9bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:claude" /></template>
