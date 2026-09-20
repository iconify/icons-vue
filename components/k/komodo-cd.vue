<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2ue8pbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2ue8pbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komodo-cd" /></template>
