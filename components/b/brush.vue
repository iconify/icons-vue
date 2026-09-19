<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy9_-jbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="xy9_-jbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:brush" /></template>
