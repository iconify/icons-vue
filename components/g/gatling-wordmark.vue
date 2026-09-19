<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5v8cfb5j.css';
import '../../css/g/gd--6wbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f5v8cfb5j"/><path class="gd--6wbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gatling-wordmark" /></template>
