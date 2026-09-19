<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx_j74_gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mx_j74_gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-return-right" /></template>
