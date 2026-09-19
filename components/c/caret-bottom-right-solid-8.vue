<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js8wydbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="js8wydbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-bottom-right-solid-8" /></template>
