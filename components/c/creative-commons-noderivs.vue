<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en_bw8biv.css';
import '../../css/c/cioxv2q3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="en_bw8biv"/><path clip-rule="evenodd" class="cioxv2q3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:creative-commons-noderivs" /></template>
