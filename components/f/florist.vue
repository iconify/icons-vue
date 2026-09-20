<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aspcfwdmv.css';
import '../../css/a/ar92us5lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<ellipse class="aspcfwdmv"/><path class="ar92us5lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:florist" /></template>
