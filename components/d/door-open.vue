<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9r3zqm1y.css';
import '../../css/t/tqpeaibww.css';
import '../../css/h/h_fsqebiz.css';
import '../../css/e/e85mzqbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9r3zqm1y wm-k"/><path class="tqpeaibww wm-k"/><path class="h_fsqebiz wm-a"/><circle class="e85mzqbit wm-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:door-open" /></template>
