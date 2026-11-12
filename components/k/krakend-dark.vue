<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnc1qr3ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pnc1qr3ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:krakend-dark" /></template>
