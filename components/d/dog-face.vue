<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qbw92nqef.css';
import '../../css/s/s8zn4lb8f.css';
import '../../css/l/lvgy32b4t.css';
import '../../css/a/a567h385m.css';
import '../../css/t/tnxf2bc6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qbw92nqef"/><path class="s8zn4lb8f"/><path class="lvgy32b4t"/><path class="a567h385m"/><path class="tnxf2bc6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:dog-face" /></template>
