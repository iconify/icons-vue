<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rf-_2pb5r.css';
import '../../css/t/tzlidozdb.css';
import '../../css/v/vu8hxubof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rf-_2pb5r"/><path class="tzlidozdb"/><path class="vu8hxubof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:boomerang" /></template>
