<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi7zzdbka.css';
import '../../css/d/d_cc7c6xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qi7zzdbka"/><path class="d_cc7c6xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lingva-translate-light" /></template>
