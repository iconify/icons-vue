<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5ryw4bkw.css';
import '../../css/s/st-osqbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="w5ryw4bkw"/><path class="st-osqbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluxer" /></template>
