<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei0d1h.css';
import '../../css/q/qa-o7h.css';
import '../../css/t/taf2xz.css';
import '../../css/f/f2o4kw.css';
import '../../css/h/hwlrmv.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei0d1h qa-o7h taf2xz"/><path class="f2o4kw qa-o7h"/><path class="hwlrmv qa-o7h taf2xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:clipboard-minus" /></template>
