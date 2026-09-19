<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysak76b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ysak76b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:car" /></template>
