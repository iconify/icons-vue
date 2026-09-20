<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa47n1b8j.css';
import '../../css/f/fkrgg3o2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pa47n1b8j"/><path class="fkrgg3o2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-lightroom" /></template>
