<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwrjgzgiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":750};
const content = `<path class="pwrjgzgiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:card" /></template>
