<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k859r6bpa.css';
import '../../css/g/gvso01jpw.css';
import '../../css/k/kezlhjxnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k859r6bpa"/><path class="gvso01jpw"/><path class="kezlhjxnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:analytics-20" /></template>
