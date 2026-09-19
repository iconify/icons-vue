<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jchvpjb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jchvpjb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-notch" /></template>
