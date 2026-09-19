<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppyon-yas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="ppyon-yas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:eject" /></template>
