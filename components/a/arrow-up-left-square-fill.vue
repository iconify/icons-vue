<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zivfc9bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zivfc9bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-left-square-fill" /></template>
