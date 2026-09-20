<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuntz5arz.css';
import '../../css/l/l9we6spoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vuntz5arz"/><path class="l9we6spoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fiberstore" /></template>
