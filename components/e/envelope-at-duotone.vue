<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knsscbb2e.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/l/lwntsjhjn.css';
import '../../css/f/ft22hdhmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knsscbb2e"/><g class="xtpeb-edw"><path class="lwntsjhjn"/><path class="ft22hdhmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:envelope-at-duotone" /></template>
