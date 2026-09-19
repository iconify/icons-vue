<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc691boul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hc691boul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-remove" /></template>
