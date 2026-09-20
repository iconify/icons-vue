<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_p2cdafc.css';
import '../../css/l/lbnij82qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_p2cdafc"/><path class="lbnij82qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fhem-dark" /></template>
