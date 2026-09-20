<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl4dl26nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl4dl26nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-square-fill" /></template>
