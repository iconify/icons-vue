<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fea_d8t0e.css';
import '../../css/i/if3pd-1ww.css';
import '../../css/a/a6rqpnekf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fea_d8t0e"/><path class="if3pd-1ww"/><path class="a6rqpnekf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:black-octagon" /></template>
