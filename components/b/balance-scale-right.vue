<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx777smff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nx777smff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:balance-scale-right" /></template>
