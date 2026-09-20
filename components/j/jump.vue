<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r491jv1-w.css';
import '../../css/s/suz6erb9m.css';
import '../../css/s/sfe1dac9u.css';
import '../../css/d/ddjrsy3wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r491jv1-w"/><path class="suz6erb9m"/><path class="sfe1dac9u"/><path class="ddjrsy3wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jump" /></template>
