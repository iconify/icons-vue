<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w09o7tbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1179,"height":1000};
const content = `<path class="w09o7tbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:chat" /></template>
