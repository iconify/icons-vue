<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy2lufbjs.css';
import '../../css/p/psqa162mc.css';
import '../../css/i/ipeafrb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy2lufbjs wm-k"/><path class="psqa162mc wm-a"/><path class="ipeafrb_f wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:banknote" /></template>
