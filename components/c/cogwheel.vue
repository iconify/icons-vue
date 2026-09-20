<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-mq8obmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-mq8obmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cogwheel" /></template>
