<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wffgbluit.css';
import '../../css/g/gl49t146u.css';
import '../../css/s/s5hl0o4ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wffgbluit"/><path class="gl49t146u"/><path class="s5hl0o4ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brick-wall-48-bold" /></template>
