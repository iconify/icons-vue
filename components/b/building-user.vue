<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykf6ek8cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ykf6ek8cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-user" /></template>
