<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx9kngbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wx9kngbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:figshare-square" /></template>
