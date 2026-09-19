<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx2ornogp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jx2ornogp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:gear-a" /></template>
