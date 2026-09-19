<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n55ad0htp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="n55ad0htp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-point-down" /></template>
