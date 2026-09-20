<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbwe8e7vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mbwe8e7vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:clock" /></template>
