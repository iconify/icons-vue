<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d1yh2db6t.css';
import '../../css/y/yi--5skpi.css';
import '../../css/e/ehj9i9bna.css';
import '../../css/u/u505mhbii.css';
import '../../css/q/qj2_kjb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="d1yh2db6t"/><path class="yi--5skpi"/><path class="ehj9i9bna"/><rect class="u505mhbii"/><path class="qj2_kjb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:jar" /></template>
