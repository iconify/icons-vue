<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/n72rw4b2e.css';
import '../../css/p/p70horb1t.css';
import '../../css/p/pojivdb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="n72rw4b2e"/><path class="p70horb1t"/><path class="pojivdb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:astronaut-01" /></template>
