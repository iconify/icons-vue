<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhh18piax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qhh18piax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:dots-horizontal-double" /></template>
