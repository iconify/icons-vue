<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_-3hmxfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_-3hmxfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librewolf-light" /></template>
