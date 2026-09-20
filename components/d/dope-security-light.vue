<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8hp5zbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p8hp5zbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dope-security-light" /></template>
