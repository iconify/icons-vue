<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyqzsr44f.css';
import '../../css/e/evgip2bmd.css';
import '../../css/e/e8wgpct6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gyqzsr44f"/><path class="evgip2bmd"/><path class="e8wgpct6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:css-map" /></template>
