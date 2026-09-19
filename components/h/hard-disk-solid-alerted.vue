<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr5vy7b3b.css';
import '../../css/f/fl1bs5brr.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted pr5vy7b3b"/><path class="clr-i-solid--alerted clr-i-solid-path-2--alerted fl1bs5brr"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:hard-disk-solid-alerted" /></template>
