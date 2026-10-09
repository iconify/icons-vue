<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-ahsnbld.css';
import '../../css/b/b8tuyrvbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h-ahsnbld"/><path class="b8tuyrvbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flag-triangle-20-bold" /></template>
