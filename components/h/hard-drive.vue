<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8hninb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="p8hninb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hard-drive" /></template>
