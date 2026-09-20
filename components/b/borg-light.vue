<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsmmuf2ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lsmmuf2ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:borg-light" /></template>
