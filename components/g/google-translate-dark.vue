<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no3pe0d-x.css';
import '../../css/c/c03hhtb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="no3pe0d-x"/><path class="c03hhtb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-translate-dark" /></template>
