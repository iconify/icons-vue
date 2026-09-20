<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfwzkkbni.css';
import '../../css/e/e7rt-sbkm.css';
import '../../css/u/ubnnzvb0h.css';
import '../../css/m/mlnhivbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yfwzkkbni"/><path class="e7rt-sbkm"/><path class="ubnnzvb0h"/><path class="mlnhivbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homescreen-hero-light" /></template>
