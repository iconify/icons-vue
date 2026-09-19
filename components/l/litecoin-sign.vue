<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6hhaib3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p6hhaib3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:litecoin-sign" /></template>
