<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-8fwsb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k-8fwsb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hewlettpackard" /></template>
