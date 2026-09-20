<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud4tzydmp.css';
import '../../css/v/vj4zwzbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ud4tzydmp"/><path class="vj4zwzbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bank-of-america" /></template>
