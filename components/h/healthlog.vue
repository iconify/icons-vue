<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nue79bcyt.css';
import '../../css/k/k237ps8_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nue79bcyt"/><path class="k237ps8_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:healthlog" /></template>
