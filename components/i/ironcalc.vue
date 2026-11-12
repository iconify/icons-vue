<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugrv1ixqz.css';
import '../../css/y/ylok2ab9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugrv1ixqz"/><path class="ylok2ab9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ironcalc" /></template>
