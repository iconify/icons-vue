<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txvldt9ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="txvldt9ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-unlock" /></template>
