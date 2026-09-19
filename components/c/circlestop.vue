<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv1trmbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qv1trmbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlestop" /></template>
