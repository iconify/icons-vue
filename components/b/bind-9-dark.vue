<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxc3l3bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxc3l3bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bind-9-dark" /></template>
