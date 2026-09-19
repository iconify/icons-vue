<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0nvg9_ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n0nvg9_ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:direction" /></template>
