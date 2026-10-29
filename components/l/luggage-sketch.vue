<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g9cwhbb5j.css';
import '../../css/g/godjt6baw.css';
import '../../css/a/aty4zjtxs.css';
import '../../css/x/xt6fe4b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g9cwhbb5j"/><path class="godjt6baw wm-a"/><path class="aty4zjtxs wm-k"/><path class="wm-a xt6fe4b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:luggage-sketch" /></template>
