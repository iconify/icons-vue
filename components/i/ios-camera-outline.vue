<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfniv6mla.css';
import '../../css/r/rl-6rnbqs.css';
import '../../css/g/gf-bxrb8a.css';
import '../../css/m/mu4n766oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mfniv6mla"/><path class="rl-6rnbqs"/><path class="gf-bxrb8a"/><circle class="mu4n766oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-camera-outline" /></template>
