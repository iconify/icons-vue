<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy901f9ms.css';
import '../../css/n/n-5kzabfr.css';
import '../../css/d/d0_q4g1fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vy901f9ms"/><path class="n-5kzabfr"/><path class="d0_q4g1fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beets-flask-dark" /></template>
