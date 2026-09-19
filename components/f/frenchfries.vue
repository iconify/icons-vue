<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyv1xibtc.css';
import '../../css/t/tzkg51bww.css';
import '../../css/v/vur1unwrn.css';
import '../../css/i/irl_dzb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gyv1xibtc"/><path class="tzkg51bww"/><path class="vur1unwrn"/><path class="irl_dzb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:frenchfries" /></template>
