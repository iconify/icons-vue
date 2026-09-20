<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cix-dhq9l.css';
import '../../css/d/dzw9pdpsm.css';
import '../../css/w/wo_l12vvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cix-dhq9l"/><rect class="dzw9pdpsm"/><path class="wo_l12vvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:cpu" /></template>
