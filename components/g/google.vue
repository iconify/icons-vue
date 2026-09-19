<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj-1rb3_g.css';
import '../../css/m/mkx0ve-2x.css';
import '../../css/a/ak63wskol.css';
import '../../css/q/q9i7kob_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wj-1rb3_g"/><path class="mkx0ve-2x"/><path class="ak63wskol"/><path class="q9i7kob_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:google" /></template>
