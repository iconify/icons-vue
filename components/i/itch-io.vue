<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz01n2b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lz01n2b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:itch-io" /></template>
