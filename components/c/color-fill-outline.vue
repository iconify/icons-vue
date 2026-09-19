<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp22x-rfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xp22x-rfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:color-fill-outline" /></template>
