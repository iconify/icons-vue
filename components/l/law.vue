<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/outyeybxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="outyeybxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:law" /></template>
