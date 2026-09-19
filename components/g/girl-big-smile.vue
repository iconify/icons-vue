<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z556wzbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z556wzbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-big-smile" /></template>
