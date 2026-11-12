<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdtvu5bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdtvu5bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-tika-binary-dark" /></template>
