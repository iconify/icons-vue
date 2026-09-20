<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfws57b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfws57b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:authelia-dark" /></template>
