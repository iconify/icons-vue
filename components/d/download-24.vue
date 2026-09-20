<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwlbydusy.css';
import '../../css/f/fshg12b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwlbydusy"/><path class="fshg12b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:download-24" /></template>
