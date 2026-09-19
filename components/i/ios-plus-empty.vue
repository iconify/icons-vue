<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0-2cj3rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c0-2cj3rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-plus-empty" /></template>
