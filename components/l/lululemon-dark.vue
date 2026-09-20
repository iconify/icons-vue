<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqns7mwxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aqns7mwxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lululemon-dark" /></template>
