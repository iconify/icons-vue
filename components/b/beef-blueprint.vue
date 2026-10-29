<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/ka54cwbgk.css';
import '../../css/h/hwzym3_4n.css';
import '../../css/v/v5jdyxbhx.css';
import '../../css/k/kmhlufbif.css';
import '../../css/c/cl_3yb3gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ka54cwbgk wm-deco"/><path class="hwzym3_4n wm-deco"/><path class="v5jdyxbhx wm-deco"/><path class="kmhlufbif wm-k"/><path class="cl_3yb3gm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:beef-blueprint" /></template>
