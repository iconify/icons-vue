<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otza0daer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otza0daer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:blinko-light" /></template>
