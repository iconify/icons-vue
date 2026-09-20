<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz5y07b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bz5y07b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iheartradio-dark" /></template>
