<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2wqhl8qw.css';
import '../../css/k/kjglpe2ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2wqhl8qw"/><path class="kjglpe2ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-brightgauge-dark" /></template>
