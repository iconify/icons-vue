<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e2f075blp.css';
import '../../css/i/i2smr173a.css';
import '../../css/m/mnsmfnpyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="e2f075blp"/><circle class="i2smr173a"/><path class="mnsmfnpyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bell-pin-duotone-line" /></template>
