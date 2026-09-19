<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc-tw6bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mc-tw6bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bolt" /></template>
