<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls8d-5bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ls8d-5bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:binoculars" /></template>
