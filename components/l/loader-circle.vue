<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/s-_v4xbgv.css';
import '../../css/i/i9whccb8f.css';
import '../../css/d/d5cjiyxkp.css';
import '../../css/r/r3gh44b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="s-_v4xbgv wm-shadow"/><path class="i9whccb8f wm-shadow"/><path class="d5cjiyxkp"/><path class="r3gh44b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:loader-circle" /></template>
