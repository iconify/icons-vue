<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/ffnnpya0h.css';
import '../../css/l/lxhba64ej.css';
import '../../css/n/ne4vkyf6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ffnnpya0h"/><path class="lxhba64ej"/><path class="ne4vkyf6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:check-rectangle" /></template>
