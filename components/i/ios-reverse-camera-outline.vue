<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2n_4vblw.css';
import '../../css/p/psnhj8bls.css';
import '../../css/c/cauo7_gzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s2n_4vblw"/><path class="psnhj8bls"/><path class="cauo7_gzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-reverse-camera-outline" /></template>
