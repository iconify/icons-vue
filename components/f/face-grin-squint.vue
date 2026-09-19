<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxg--5aum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxg--5aum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin-squint" /></template>
