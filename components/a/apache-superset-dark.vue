<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wff71wb4h.css';
import '../../css/t/t01rqxb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wff71wb4h"/><path class="t01rqxb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-superset-dark" /></template>
