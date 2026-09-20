<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk7aafmee.css';
import '../../css/x/xtb6wpbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sk7aafmee"/><path class="xtb6wpbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:american-airlines-light" /></template>
