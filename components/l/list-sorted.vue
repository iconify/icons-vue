<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6t6jkvfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w6t6jkvfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:list-sorted" /></template>
