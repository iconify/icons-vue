<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh7z1bckc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qh7z1bckc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hands-praying" /></template>
