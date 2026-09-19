<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux8ahf0rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ux8ahf0rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ember" /></template>
