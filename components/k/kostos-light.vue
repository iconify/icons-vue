<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0-fyacpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c0-fyacpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kostos-light" /></template>
