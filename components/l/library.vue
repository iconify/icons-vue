<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/uurmy6bna.css';
import '../../css/e/eivsv4x-i.css';
import '../../css/d/d7sz30-lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uurmy6bna"/><rect class="eivsv4x-i"/><path class="d7sz30-lr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:library" /></template>
