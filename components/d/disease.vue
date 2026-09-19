<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imvhqx18h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imvhqx18h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:disease" /></template>
