<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trq7glk2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trq7glk2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:check-double" /></template>
