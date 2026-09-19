<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycwl5bckj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ycwl5bckj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:lock-open" /></template>
