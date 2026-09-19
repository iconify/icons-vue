<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fys1ehhsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fys1ehhsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:browserslist" /></template>
