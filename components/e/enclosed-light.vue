<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vluw-lfyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vluw-lfyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:enclosed-light" /></template>
