<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqvwqo0sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqvwqo0sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hetrixtools-light" /></template>
