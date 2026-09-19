<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxke6-btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":621};
const content = `<path class="xxke6-btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:addstar" /></template>
