<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znversx8x.css';
import '../../css/x/x4xm00rnt.css';
import '../../css/n/nc2ovs5_q.css';
import '../../css/a/a-8ulvb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a znversx8x"/><path class="wm-k x4xm00rnt"/><path class="nc2ovs5_q wm-k"/><path class="a-8ulvb8e wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:fuel" /></template>
