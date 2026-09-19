<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tip2o2__i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tip2o2__i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dungeon" /></template>
