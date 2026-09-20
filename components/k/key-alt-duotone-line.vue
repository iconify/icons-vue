<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nxahim30c.css';
import '../../css/v/vapgi1b5o.css';
import '../../css/i/ip-75_awg.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGECSMuaCC"><g class="ft5dv1b6b"><path class="nxahim30c"/><circle class="vapgi1b5o"/><path class="ip-75_awg"/></g></mask></defs><path mask="url(#SVGECSMuaCC)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:key-alt-duotone-line" /></template>
