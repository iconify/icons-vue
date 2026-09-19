<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsl2t2bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xsl2t2bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:circle" /></template>
