<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjuv6rb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":424};
const content = `<path class="kjuv6rb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:language-html5" /></template>
