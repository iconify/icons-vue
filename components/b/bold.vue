<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frw9aro9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="frw9aro9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bold" /></template>
