<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ie_33mcru.css';
import '../../css/p/pc6eh-ilv.css';
import '../../css/v/v7v_u0jql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ie_33mcru"/><path class="pc6eh-ilv"/><path class="v7v_u0jql wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dog" /></template>
