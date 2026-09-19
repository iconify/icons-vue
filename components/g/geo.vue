<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7p4sbcuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="j7p4sbcuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:geo" /></template>
