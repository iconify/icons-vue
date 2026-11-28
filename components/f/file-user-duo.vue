<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibyp8rb4m.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g41oqhzpy.css';
import '../../css/i/ixg3tzbda.css';
import '../../css/q/qtpprbcqy.css';
import '../../css/i/itkowf82a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibyp8rb4m secondary"/><g class="dt0cm9dhy primary"><path class="g41oqhzpy"/><path class="ixg3tzbda"/><path class="qtpprbcqy"/><path class="itkowf82a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-user-duo" /></template>
