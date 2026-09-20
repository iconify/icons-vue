<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm76dsbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wm76dsbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filedrop" /></template>
