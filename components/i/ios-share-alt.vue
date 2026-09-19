<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grmy6--qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grmy6--qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-share-alt" /></template>
