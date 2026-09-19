<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl6dnvbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dl6dnvbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-male" /></template>
