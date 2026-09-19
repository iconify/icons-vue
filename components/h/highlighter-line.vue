<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpruxlbdl.css';
import '../../css/v/vwzjakbln.css';
import '../../css/d/d8q72uf0l.css';
import '../../css/t/tz9fk5b6c.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 mpruxlbdl"/><path class="clr-i-outline clr-i-outline-path-2 vwzjakbln"/><path class="clr-i-outline clr-i-outline-path-3 d8q72uf0l"/><path class="clr-i-outline clr-i-outline-path-4 tz9fk5b6c"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:highlighter-line" /></template>
