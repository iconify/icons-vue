<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kduu9pbdz.css';
import '../../css/n/nsxom22ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kduu9pbdz"/><path class="nsxom22ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:css3-dark" /></template>
