<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwjdabcpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwjdabcpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:davical-light" /></template>
