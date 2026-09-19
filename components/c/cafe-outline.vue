<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0kfxub6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0kfxub6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cafe-outline" /></template>
