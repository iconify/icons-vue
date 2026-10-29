<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daj2-25di.css';
import '../../css/o/otjao6b_l.css';
import '../../css/h/h8crmjbcu.css';
import '../../css/v/vs2edu79l.css';
import '../../css/q/quso6qb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daj2-25di wm-shadow"/><path class="otjao6b_l wm-k"/><path class="h8crmjbcu wm-k"/><path class="vs2edu79l wm-a"/><path class="quso6qb-x wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:chevron-last" /></template>
