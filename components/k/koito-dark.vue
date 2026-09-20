<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4a4ftbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4a4ftbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:koito-dark" /></template>
