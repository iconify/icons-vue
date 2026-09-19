<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2i48dbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="t2i48dbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:assignment-returned" /></template>
