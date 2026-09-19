<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypj23acfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="ypj23acfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:call" /></template>
