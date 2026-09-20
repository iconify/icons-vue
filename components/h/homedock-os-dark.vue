<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj64-jb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vj64-jb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homedock-os-dark" /></template>
