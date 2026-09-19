<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msf02b-ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="msf02b-ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:flickr" /></template>
