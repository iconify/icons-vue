<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v454e9bix.css';
import '../../css/j/jjdvkvbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v454e9bix"/><path class="jjdvkvbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-commit-20" /></template>
