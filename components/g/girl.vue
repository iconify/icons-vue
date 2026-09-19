<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2c1ccccv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2c1ccccv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl" /></template>
