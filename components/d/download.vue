<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdr9u_apw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdr9u_apw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:download" /></template>
