<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du0fstbco.css';
import '../../css/d/da5se5sef.css';
import '../../css/m/mle8vwbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="du0fstbco"/><path class="da5se5sef"/><path class="mle8vwbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ipfs-dark" /></template>
