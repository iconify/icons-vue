<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrktzrbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yrktzrbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-right-from-tall-rectangle-outline" /></template>
