<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp3n9jxlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qp3n9jxlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lens" /></template>
