<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/capp2ob6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="capp2ob6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:children" /></template>
