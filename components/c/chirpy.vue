<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdrsexbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdrsexbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chirpy" /></template>
