<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfptr2-1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfptr2-1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-checkmark-empty" /></template>
