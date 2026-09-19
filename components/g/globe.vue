<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czg1q2ikv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="czg1q2ikv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:globe" /></template>
