<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r10ma0e2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r10ma0e2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-after-effects-light" /></template>
