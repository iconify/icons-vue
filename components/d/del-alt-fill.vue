<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p_jfne-ha.css';
import '../../css/b/b04w6ibzc.css';
import '../../css/x/xus_l3b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><ellipse class="p_jfne-ha"/><path class="b04w6ibzc"/><path class="xus_l3b-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:del-alt-fill" /></template>
