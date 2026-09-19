<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5vhxnbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y5vhxnbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:compress-arrows-alt" /></template>
