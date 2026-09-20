<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_h0j5bwz.css';
import '../../css/o/o27nl8m4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m_h0j5bwz"/><path clip-rule="evenodd" class="o27nl8m4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:kubernetes" /></template>
