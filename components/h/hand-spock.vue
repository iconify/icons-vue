<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym7n7kbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ym7n7kbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-spock" /></template>
