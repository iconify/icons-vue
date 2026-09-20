<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nim0ecb_g.css';
import '../../css/m/m2lf37b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nim0ecb_g"/><path class="m2lf37b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-messages-dark" /></template>
