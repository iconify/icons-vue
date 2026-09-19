<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkqps8bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="gkqps8bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bacteria" /></template>
