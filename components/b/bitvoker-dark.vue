<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq0mgtbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wq0mgtbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitvoker-dark" /></template>
