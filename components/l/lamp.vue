<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqsj_wbmh.css';
import '../../css/a/a6f9j-74o.css';
import '../../css/k/k_-hq8bfm.css';
import '../../css/l/l88ep297x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqsj_wbmh"/><path class="a6f9j-74o"/><path class="k_-hq8bfm"/><path class="l88ep297x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:lamp" /></template>
