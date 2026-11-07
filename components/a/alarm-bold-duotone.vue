<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_-_yx_oi.css';
import '../../css/g/gfnljuhlb.css';
import '../../css/k/kube8drda.css';
import '../../css/j/jf1pbcbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_-_yx_oi"/><path class="gfnljuhlb"/><path class="kube8drda"/><path class="jf1pbcbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-bold-duotone" /></template>
