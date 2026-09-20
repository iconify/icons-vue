<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/we9bzfb3x.css';
import '../../css/v/vyo2c1b7n.css';
import '../../css/o/owdh_1sjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="we9bzfb3x"/><path class="vyo2c1b7n"/><path class="owdh_1sjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cloud-network-1" /></template>
