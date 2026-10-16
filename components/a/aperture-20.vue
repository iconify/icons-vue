<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw3xaacjo.css';
import '../../css/b/b0od6kv7t.css';
import '../../css/d/dpjrf_bzd.css';
import '../../css/d/dojkwjbbv.css';
import '../../css/r/re1kdkqkj.css';
import '../../css/v/vfituccbc.css';
import '../../css/s/s1g5ck_5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="b0od6kv7t"/><path class="dpjrf_bzd"/><path class="dojkwjbbv"/><path class="re1kdkqkj"/><path class="vfituccbc"/><path class="s1g5ck_5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aperture-20" /></template>
