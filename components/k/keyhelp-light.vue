<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9vj76spy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9vj76spy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keyhelp-light" /></template>
