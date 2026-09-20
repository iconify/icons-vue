<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc0s-3bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uc0s-3bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowdsec-light" /></template>
