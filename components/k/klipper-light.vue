<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzma84bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fzma84bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:klipper-light" /></template>
