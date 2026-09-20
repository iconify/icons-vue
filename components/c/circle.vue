<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrsxhn-mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jrsxhn-mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:circle" /></template>
