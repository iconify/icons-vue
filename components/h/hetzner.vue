<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv0s7yb0o.css';
import '../../css/d/da9g56non.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="rv0s7yb0o"/><path class="da9g56non"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hetzner" /></template>
