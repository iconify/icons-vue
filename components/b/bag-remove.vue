<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4bl5-b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4bl5-b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bag-remove" /></template>
