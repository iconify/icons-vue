<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnl2rfb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gnl2rfb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:fedora" /></template>
