<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxrlaebjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lxrlaebjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homebox-light" /></template>
