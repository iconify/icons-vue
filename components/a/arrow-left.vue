<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h9zga6crh.css';
import '../../css/p/px0ziu5wp.css';
import '../../css/t/tfvxc6bdj.css';
import '../../css/w/wni2p7b5b.css';
import '../../css/i/i81x87zzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h9zga6crh wm-deco"/><path class="px0ziu5wp wm-k"/><path class="tfvxc6bdj wm-k"/><path class="wm-k wni2p7b5b"/><path class="i81x87zzc wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:arrow-left" /></template>
