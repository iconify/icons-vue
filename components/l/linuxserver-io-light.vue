<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r66o14bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r66o14bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linuxserver-io-light" /></template>
