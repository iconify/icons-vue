<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8zb9sb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="z8zb9sb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:battery-0" /></template>
