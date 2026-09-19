<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaivl163v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kaivl163v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:comments" /></template>
