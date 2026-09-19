<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z07rjrbqz.css';
import '../../css/v/v5_5mr8sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z07rjrbqz"/><path class="v5_5mr8sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:document-text-outline" /></template>
