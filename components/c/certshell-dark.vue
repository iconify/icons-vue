<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdqagrbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdqagrbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:certshell-dark" /></template>
