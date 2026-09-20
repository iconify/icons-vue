<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twv9pbpkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="twv9pbpkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:democrat-solid" /></template>
