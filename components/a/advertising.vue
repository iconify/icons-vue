<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5ddfu79i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f5ddfu79i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:advertising" /></template>
