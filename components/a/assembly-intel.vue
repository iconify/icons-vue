<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv762_3ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv762_3ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-intel" /></template>
