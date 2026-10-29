<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gckbdacgp.css';
import '../../css/g/gt3_0hbgl.css';
import '../../css/x/xqpnc4m6o.css';
import '../../css/g/go5n_1h8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gckbdacgp"/><path class="gt3_0hbgl wm-s"/><path class="xqpnc4m6o"/><path class="go5n_1h8p wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:battery-charging-duo" /></template>
