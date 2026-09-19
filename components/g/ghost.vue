<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr-75kbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="tr-75kbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ghost" /></template>
