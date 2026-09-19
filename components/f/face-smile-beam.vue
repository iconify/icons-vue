<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd7v6vbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bd7v6vbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:face-smile-beam" /></template>
