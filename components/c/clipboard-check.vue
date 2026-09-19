<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv9k0bb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xv9k0bb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:clipboard-check" /></template>
