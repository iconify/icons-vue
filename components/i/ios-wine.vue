<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvgeeccfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zvgeeccfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-wine" /></template>
