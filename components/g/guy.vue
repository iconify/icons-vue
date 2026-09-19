<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qof5i9bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qof5i9bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy" /></template>
