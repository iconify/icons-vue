<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sgsrnm8tv.css';
import '../../css/j/jfl1m_hze.css';
import '../../css/g/gv6pv-b2u.css';
import '../../css/k/kf3ab9vwr.css';
import '../../css/f/fin7epbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="sgsrnm8tv"/><path class="jfl1m_hze"/><path class="gv6pv-b2u"/><path class="kf3ab9vwr"/><path class="fin7epbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:electron" /></template>
