<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-fgwj31d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="c-fgwj31d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-holding" /></template>
