<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7lqgabtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="b7lqgabtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:dribbble" /></template>
