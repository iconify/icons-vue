<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap3nt-pxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="ap3nt-pxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:facto" /></template>
