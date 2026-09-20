<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0ulh_r9o.css';
import '../../css/f/f_rwg-r9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="a0ulh_r9o"/><path class="f_rwg-r9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grav" /></template>
