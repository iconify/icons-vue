<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lin5v0buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lin5v0buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:genderless" /></template>
