<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4aenxb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h4aenxb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:compass" /></template>
