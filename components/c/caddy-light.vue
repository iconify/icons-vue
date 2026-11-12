<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cybvs067u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cybvs067u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:caddy-light" /></template>
