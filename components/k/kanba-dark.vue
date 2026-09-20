<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z441hubzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z441hubzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kanba-dark" /></template>
