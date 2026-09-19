<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2yeubbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m2yeubbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bin-xmark" /></template>
