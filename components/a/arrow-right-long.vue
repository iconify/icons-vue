<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arjc7_bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="arjc7_bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-right-long" /></template>
