<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esa02sbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="esa02sbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:asterisk-20" /></template>
