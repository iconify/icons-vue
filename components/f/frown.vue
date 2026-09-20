<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wky32j_ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wky32j_ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:frown" /></template>
