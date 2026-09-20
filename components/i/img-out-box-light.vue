<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o98ro-b0q.css';
import '../../css/q/qgy99obou.css';
import '../../css/r/r17ye20_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o98ro-b0q"/><path clip-rule="evenodd" class="qgy99obou"/><path class="r17ye20_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:img-out-box-light" /></template>
