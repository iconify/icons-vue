<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_9kmbbto.css';
import '../../css/q/qjhlvsb3i.css';
import '../../css/q/qj361nbje.css';
import '../../css/d/dmcxc0b0p.css';
import '../../css/e/e1p6d4b6r.css';
import '../../css/c/cia76rb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_9kmbbto"/><path class="qjhlvsb3i"/><path class="qj361nbje"/><path class="dmcxc0b0p"/><path class="e1p6d4b6r"/><path class="cia76rb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:anchor" /></template>
